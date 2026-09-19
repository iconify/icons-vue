<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikh0lz1vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikh0lz1vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:imac" /></template>
