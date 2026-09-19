<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxoppz7ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gxoppz7ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:lymph-nodes-outline" /></template>
