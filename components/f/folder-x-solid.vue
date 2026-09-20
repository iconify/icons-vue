<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4jevqhgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4jevqhgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:folder-x-solid" /></template>
