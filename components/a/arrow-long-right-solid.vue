<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebc0syb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebc0syb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:arrow-long-right-solid" /></template>
