<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eafkvu7mu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eafkvu7mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-up-circle-solid" /></template>
