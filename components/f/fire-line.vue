<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zip9yv1tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zip9yv1tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fire-line" /></template>
