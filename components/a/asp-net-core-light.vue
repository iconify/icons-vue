<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r31wnti5m.css';
import '../../css/i/i5za_y8px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r31wnti5m"/><path class="i5za_y8px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:asp-net-core-light" /></template>
