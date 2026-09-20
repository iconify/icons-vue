<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt2t-006k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt2t-006k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:head-side" /></template>
