<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8q0-j4-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u8q0-j4-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:forward-solid" /></template>
