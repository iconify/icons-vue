<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su3hmfhdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su3hmfhdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:banana" /></template>
