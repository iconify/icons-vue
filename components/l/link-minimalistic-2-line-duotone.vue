<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pi6xz2b_n.css';
import '../../css/d/dtoolxbmj.css';
import '../../css/n/nvxxmxb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pi6xz2b_n"/><path class="dtoolxbmj"/><path class="nvxxmxb7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-minimalistic-2-line-duotone" /></template>
