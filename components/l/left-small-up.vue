<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e01otg9wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e01otg9wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:left-small-up" /></template>
