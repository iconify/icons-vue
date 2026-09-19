<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wec_rkbwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wec_rkbwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:lock" /></template>
