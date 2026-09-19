<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_qkk_bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_qkk_bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:camera" /></template>
