<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj4db04ha.css';
import '../../css/x/xr7c334jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wj4db04ha"/><path class="xr7c334jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:exclamation-triangle-stroke-20" /></template>
