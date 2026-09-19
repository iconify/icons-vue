<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckwg36bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckwg36bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:dribbble" /></template>
