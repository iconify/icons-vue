<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hradpqb8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="hradpqb8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:arrow-bottom-right" /></template>
