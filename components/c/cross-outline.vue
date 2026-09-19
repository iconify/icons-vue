<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvnlcab3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvnlcab3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:cross-outline" /></template>
