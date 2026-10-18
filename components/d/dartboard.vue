<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx7t24bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx7t24bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dartboard" /></template>
