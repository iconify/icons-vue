<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5j4oqb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v5j4oqb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:invest-monitor" /></template>
