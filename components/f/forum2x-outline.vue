<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy9qmtbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dy9qmtbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:forum2x-outline" /></template>
