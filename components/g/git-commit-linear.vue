<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sduv6uq4w.css';
import '../../css/u/u1yvpnjhe.css';
import '../../css/z/zfk5qrblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sduv6uq4w"/><path class="u1yvpnjhe"/><path class="zfk5qrblp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-commit-linear" /></template>
