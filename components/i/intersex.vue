<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blju_tb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":19,"height":24};
const content = `<path class="blju_tb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:intersex" /></template>
