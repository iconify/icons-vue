<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbcdmtbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbcdmtbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:debug-alt" /></template>
