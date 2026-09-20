<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o51wkobzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o51wkobzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-center-stretch" /></template>
