<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0ldfib_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e0ldfib_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:binding-01" /></template>
