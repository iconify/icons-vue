<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvu5-paxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="tvu5-paxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:arrow-circle-up" /></template>
