<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqg11dbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":487,"height":775};
const content = `<path class="mqg11dbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:4" /></template>
