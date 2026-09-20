<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbjyl9bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xbjyl9bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:graduation-cap" /></template>
