<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i592gf__t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i592gf__t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:airplane-plus" /></template>
