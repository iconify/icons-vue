<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1xs5rgbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1xs5rgbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:clock-fill" /></template>
