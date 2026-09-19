<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oky91eb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oky91eb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:close" /></template>
