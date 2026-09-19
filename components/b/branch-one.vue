<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8n_clbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g8n_clbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:branch-one" /></template>
