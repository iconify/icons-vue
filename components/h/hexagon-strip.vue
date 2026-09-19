<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs_kw9bbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xs_kw9bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:hexagon-strip" /></template>
