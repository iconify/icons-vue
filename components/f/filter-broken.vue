<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbc3x4ajk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbc3x4ajk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:filter-broken" /></template>
