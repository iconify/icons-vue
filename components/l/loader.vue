<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4vexcbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4vexcbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:loader" /></template>
