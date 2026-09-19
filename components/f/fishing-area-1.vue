<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv6eoc9-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv6eoc9-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:fishing-area-1" /></template>
