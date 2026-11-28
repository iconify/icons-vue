<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbcahyb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbcahyb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:clover-solid" /></template>
