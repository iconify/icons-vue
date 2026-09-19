<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r33gxlsoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r33gxlsoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:arrow-go-forward" /></template>
