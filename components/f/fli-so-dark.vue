<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc_a9dblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bc_a9dblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fli-so-dark" /></template>
