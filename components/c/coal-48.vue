<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q70bmjh4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q70bmjh4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coal-48" /></template>
