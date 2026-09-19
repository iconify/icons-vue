<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf-m5_bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="zf-m5_bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:hourglass" /></template>
