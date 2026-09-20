<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4xnnr36c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4xnnr36c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-up-double-fill" /></template>
