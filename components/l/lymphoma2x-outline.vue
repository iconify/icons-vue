<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2pn15bdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v2pn15bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:lymphoma2x-outline" /></template>
