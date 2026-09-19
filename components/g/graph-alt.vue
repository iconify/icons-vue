<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_6d62ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="h_6d62ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:graph-alt" /></template>
