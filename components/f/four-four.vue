<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6l2gp-bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k6l2gp-bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:four-four" /></template>
