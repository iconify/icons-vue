<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe5jq2kzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="pe5jq2kzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:canoe" /></template>
