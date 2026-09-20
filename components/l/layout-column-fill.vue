<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk7lehbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk7lehbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-column-fill" /></template>
