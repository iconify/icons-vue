<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_9n7s0do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_9n7s0do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:help-outline" /></template>
