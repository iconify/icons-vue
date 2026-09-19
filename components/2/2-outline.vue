<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0i5ozbxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h0i5ozbxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:2-outline" /></template>
