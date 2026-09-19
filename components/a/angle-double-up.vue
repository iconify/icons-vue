<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgyx6_bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="xgyx6_bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:angle-double-up" /></template>
