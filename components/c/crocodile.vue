<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz418kbmm.css';
import '../../css/t/tozovebkm.css';
import '../../css/w/wak66kbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fz418kbmm"/><path class="tozovebkm"/><path class="wak66kbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:crocodile" /></template>
