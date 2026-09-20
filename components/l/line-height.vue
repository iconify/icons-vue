<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfxt1osmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="vfxt1osmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:line-height" /></template>
