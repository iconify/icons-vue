<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4tob8bkg.css';
import '../../css/p/p4bqiyolx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w4tob8bkg"/><path class="p4bqiyolx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:home-outline" /></template>
