<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4-48zo7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v4-48zo7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bandaged" /></template>
