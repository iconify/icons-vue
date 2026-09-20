<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvwtqr81i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvwtqr81i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:laptop-windows" /></template>
