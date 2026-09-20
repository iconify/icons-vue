<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpo_5g0im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpo_5g0im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kik" /></template>
