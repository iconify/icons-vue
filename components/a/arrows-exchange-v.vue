<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvz5bs72g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvz5bs72g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrows-exchange-v" /></template>
