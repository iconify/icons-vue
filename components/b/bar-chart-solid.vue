<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlxnel37i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wlxnel37i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bar-chart-solid" /></template>
