<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlxtf-b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qlxtf-b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:3" /></template>
