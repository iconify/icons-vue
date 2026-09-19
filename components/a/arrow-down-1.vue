<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw4b39bqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gw4b39bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-down-1" /></template>
