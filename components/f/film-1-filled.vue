<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgv2o1bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgv2o1bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:film-1-filled" /></template>
