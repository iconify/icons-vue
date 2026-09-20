<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d56dqs-ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="d56dqs-ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:erlenmeyer-flask" /></template>
