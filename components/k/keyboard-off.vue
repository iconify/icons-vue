<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is8gm10_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is8gm10_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:keyboard-off" /></template>
