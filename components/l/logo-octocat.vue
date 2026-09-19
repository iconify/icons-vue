<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzpmrsbbt.css';
import '../../css/y/yg_pakoyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kzpmrsbbt"/><path class="yg_pakoyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-octocat" /></template>
