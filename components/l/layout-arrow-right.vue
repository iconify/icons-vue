<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk8cjobyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk8cjobyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layout-arrow-right" /></template>
