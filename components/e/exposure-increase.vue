<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxbsm8b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxbsm8b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:exposure-increase" /></template>
