<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dss7b2x8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dss7b2x8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:book-1-solid" /></template>
