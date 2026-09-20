<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4isnxbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="m4isnxbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:fahrenheit-solid" /></template>
