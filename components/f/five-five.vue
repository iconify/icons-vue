<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr8spdb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vr8spdb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:five-five" /></template>
