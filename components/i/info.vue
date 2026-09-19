<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk_fp9bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jk_fp9bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:info" /></template>
