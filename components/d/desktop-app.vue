<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge6-751ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ge6-751ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:desktop-app" /></template>
