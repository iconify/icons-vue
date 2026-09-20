<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc2e1cbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc2e1cbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-sidebar" /></template>
