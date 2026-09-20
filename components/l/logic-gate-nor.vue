<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-joht71n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-joht71n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:logic-gate-nor" /></template>
