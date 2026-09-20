<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4_wkcoza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="w4_wkcoza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:jewelry-store-11" /></template>
