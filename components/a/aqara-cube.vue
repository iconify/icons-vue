<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1pyt9scc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1pyt9scc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-cube" /></template>
