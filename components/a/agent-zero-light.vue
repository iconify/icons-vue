<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usdkizb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="usdkizb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:agent-zero-light" /></template>
