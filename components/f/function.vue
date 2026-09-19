<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdnkc-v7d.css';
import '../../css/p/pd8vq-blm.css';
import '../../css/u/u0ofk_h1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fdnkc-v7d"/><path class="pd8vq-blm"/><path class="u0ofk_h1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:function" /></template>
