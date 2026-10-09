<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7n36ms-b.css';
import '../../css/a/a1wp-ubtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x7n36ms-b"/><path class="a1wp-ubtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-open-48-bold" /></template>
