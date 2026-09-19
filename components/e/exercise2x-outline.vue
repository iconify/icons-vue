<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyp6cc8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cuyp6cc8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:exercise2x-outline" /></template>
