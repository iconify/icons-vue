<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9800dbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="h9800dbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:lightning-alt" /></template>
