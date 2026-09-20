<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5y0mrhjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5y0mrhjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:gift-solid" /></template>
