<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb0ge_b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb0ge_b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:layout-columns-solid" /></template>
