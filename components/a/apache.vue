<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3bji0brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3bji0brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:apache" /></template>
