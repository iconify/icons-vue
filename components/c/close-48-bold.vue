<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glxb9obxa.css';
import '../../css/r/rbj7ts9zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="glxb9obxa"/><path class="rbj7ts9zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:close-48-bold" /></template>
