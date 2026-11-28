<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uph89jbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uph89jbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bot-check" /></template>
