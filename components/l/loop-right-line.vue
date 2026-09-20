<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra5khdb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra5khdb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:loop-right-line" /></template>
