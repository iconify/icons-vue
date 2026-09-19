<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv094-b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hv094-b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:checklist" /></template>
