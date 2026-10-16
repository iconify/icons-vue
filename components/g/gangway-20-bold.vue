<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fscbk5btm.css';
import '../../css/i/i1rcpxbal.css';
import '../../css/l/lk_wy274k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fscbk5btm"/><path class="i1rcpxbal"/><path class="lk_wy274k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gangway-20-bold" /></template>
