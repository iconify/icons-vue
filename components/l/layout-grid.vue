<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn8i55zho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn8i55zho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:layout-grid" /></template>
