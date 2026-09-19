<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mn62l3n5r.css';
import '../../css/y/yx6v_jgke.css';
import '../../css/c/cb8u71hty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mn62l3n5r"/><path class="yx6v_jgke"/><path class="cb8u71hty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:camera-off-01" /></template>
