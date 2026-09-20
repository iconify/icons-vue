<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x61iccc4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x61iccc4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrow-down-left" /></template>
