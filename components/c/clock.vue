<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it60jpd0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="it60jpd0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:clock" /></template>
