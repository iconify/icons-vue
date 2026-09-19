<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spzykfbbj.css';
import '../../css/c/cdisl5apr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spzykfbbj"/><path class="cdisl5apr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-map-pin" /></template>
