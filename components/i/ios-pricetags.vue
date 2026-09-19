<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f832m7bua.css';
import '../../css/e/e5rlcgb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f832m7bua"/><path class="e5rlcgb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-pricetags" /></template>
