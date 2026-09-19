<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzo4dpbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="vzo4dpbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:file" /></template>
