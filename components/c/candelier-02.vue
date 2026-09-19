<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sufajj_zr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sufajj_zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:candelier-02" /></template>
