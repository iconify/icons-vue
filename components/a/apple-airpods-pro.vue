<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgrfg_3le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgrfg_3le"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:apple-airpods-pro" /></template>
