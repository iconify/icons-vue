<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyqnu2ioa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyqnu2ioa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:eight-solid" /></template>
