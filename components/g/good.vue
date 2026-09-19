<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro79hccfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ro79hccfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:good" /></template>
