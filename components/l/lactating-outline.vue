<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up1io4b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="up1io4b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:lactating-outline" /></template>
