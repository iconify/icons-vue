<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o4bztxbcd.css';
import '../../css/w/w3kf-ubcm.css';
import '../../css/k/k-a-0dber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o4bztxbcd"/><path class="w3kf-ubcm"/><path class="k-a-0dber"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bookmark-opened-line-duotone" /></template>
