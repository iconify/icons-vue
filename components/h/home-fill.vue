<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyhtppbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyhtppbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:home-fill" /></template>
