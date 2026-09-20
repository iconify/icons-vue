<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afdx_obcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afdx_obcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bulb-group-off-outline" /></template>
