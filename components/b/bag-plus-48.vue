<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb2gho-_w.css';
import '../../css/e/e6f488wbx.css';
import '../../css/c/c4_zttl1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cb2gho-_w"/><path class="e6f488wbx"/><path class="c4_zttl1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bag-plus-48" /></template>
