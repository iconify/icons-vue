<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpkjll-eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rpkjll-eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:5-outline" /></template>
