<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oatx3zzgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-2};
const content = `<path class="oatx3zzgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:ice-cream" /></template>
