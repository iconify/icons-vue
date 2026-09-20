<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csipk0bxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csipk0bxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloud-sun-solid" /></template>
