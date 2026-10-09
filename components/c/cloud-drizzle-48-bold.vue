<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0lht2fqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m0lht2fqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-drizzle-48-bold" /></template>
