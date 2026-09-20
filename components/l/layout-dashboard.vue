<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h71f35jbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h71f35jbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layout-dashboard" /></template>
