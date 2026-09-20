<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/z5l_mobdk.css';
import '../../css/g/g121b32ky.css';
import '../../css/e/etg41e6bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="z5l_mobdk"/><path class="g121b32ky"/><path class="etg41e6bw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:add-broken" /></template>
