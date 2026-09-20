<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrrdjo_kl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrrdjo_kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:boxy-svg" /></template>
