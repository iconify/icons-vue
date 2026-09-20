<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea2px6x9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="ea2px6x9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:archive" /></template>
