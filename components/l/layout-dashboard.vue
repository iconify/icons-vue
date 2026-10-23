<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug1puvbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug1puvbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layout-dashboard" /></template>
