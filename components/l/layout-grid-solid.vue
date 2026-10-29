<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gugd7gbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gugd7gbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:layout-grid-solid" /></template>
