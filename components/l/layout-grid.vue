<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iam4o5jjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iam4o5jjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layout-grid" /></template>
