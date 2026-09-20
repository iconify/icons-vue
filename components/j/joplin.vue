<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-t4bybfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-t4bybfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:joplin" /></template>
