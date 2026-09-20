<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oh6_ibb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="oh6_ibb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:atom-solid" /></template>
