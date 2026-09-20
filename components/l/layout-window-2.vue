<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlt7b8b6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="dlt7b8b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:layout-window-2" /></template>
