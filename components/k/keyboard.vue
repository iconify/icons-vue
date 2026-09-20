<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7kuv-whh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7kuv-whh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard" /></template>
