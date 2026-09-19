<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3k-2m9tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3k-2m9tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bridges-v2" /></template>
