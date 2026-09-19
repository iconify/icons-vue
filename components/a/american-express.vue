<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1cizuuko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d1cizuuko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:american-express" /></template>
