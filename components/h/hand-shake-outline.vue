<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vipbm3bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vipbm3bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:hand-shake-outline" /></template>
