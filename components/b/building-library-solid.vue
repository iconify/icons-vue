<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/swosvdkra.css';
import '../../css/f/f11xt5mlf.css';
import '../../css/d/de49kbcou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="swosvdkra"/><path clip-rule="evenodd" class="f11xt5mlf"/><path class="de49kbcou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:building-library-solid" /></template>
