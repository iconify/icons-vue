<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1ogsjsal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1ogsjsal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layout-grid-circles-filled" /></template>
