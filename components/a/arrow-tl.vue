<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc056bbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc056bbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-tl" /></template>
