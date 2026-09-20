<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh8i5_bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh8i5_bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fx" /></template>
