<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjw2pb06u.css';
import '../../css/e/e55pc6bqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mjw2pb06u"/><path class="e55pc6bqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:earthquake-48-bold" /></template>
