<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu8b-ibsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu8b-ibsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heading-4" /></template>
