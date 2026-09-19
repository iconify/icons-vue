<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2-2uepmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r2-2uepmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:left-small" /></template>
