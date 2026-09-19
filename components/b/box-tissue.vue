<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1fimrb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r1fimrb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:box-tissue" /></template>
