<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb-7oac9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rb-7oac9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:align-text-right" /></template>
