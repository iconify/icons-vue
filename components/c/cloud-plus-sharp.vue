<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl5bsbfss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl5bsbfss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-plus-sharp" /></template>
