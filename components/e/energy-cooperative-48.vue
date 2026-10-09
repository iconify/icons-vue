<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec6pe6b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ec6pe6b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-cooperative-48" /></template>
