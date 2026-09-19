<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5bqtg6rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="m5bqtg6rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:camera" /></template>
