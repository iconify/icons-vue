<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipx3pgbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipx3pgbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:external-link" /></template>
