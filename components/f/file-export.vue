<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xr9j7pbzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xr9j7pbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:file-export" /></template>
