<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty8-mztlv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty8-mztlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-left-up-circle-fill" /></template>
