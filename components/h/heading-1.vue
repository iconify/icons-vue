<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sipm7-qkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sipm7-qkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:heading-1" /></template>
