<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfex-6f3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfex-6f3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:hanger" /></template>
