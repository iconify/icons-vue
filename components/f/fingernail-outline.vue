<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cafk4nbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cafk4nbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:fingernail-outline" /></template>
