<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6a025wpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-3};
const content = `<path class="d6a025wpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:beer" /></template>
