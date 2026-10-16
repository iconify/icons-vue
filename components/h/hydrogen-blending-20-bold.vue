<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke-cmwbjg.css';
import '../../css/z/zthy_-bth.css';
import '../../css/r/r50nl1bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ke-cmwbjg"/><path class="zthy_-bth"/><path class="r50nl1bwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-blending-20-bold" /></template>
