<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b4q8hn6zn.css';
import '../../css/z/z78z6ac7w.css';
import '../../css/r/r5aur-b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b4q8hn6zn"/><path class="z78z6ac7w"/><path class="r5aur-b7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle-dollar-sign" /></template>
