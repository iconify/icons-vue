<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-amvrbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p-amvrbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:g-outline" /></template>
