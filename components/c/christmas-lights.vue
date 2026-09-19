<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5r6hkb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5r6hkb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:christmas-lights" /></template>
