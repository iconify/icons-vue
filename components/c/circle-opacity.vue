<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbp5xr6qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbp5xr6qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:circle-opacity" /></template>
