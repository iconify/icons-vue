<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-pbe_bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-pbe_bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cherry" /></template>
