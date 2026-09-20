<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll1w1k65i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ll1w1k65i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-right-2" /></template>
