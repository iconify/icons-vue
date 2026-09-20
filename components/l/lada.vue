<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq2_cn6qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq2_cn6qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lada" /></template>
