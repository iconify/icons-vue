<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfdvoybwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rfdvoybwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hulu" /></template>
