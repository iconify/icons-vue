<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwic1hbgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwic1hbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bandr-automation" /></template>
