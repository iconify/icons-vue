<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_2i16b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_2i16b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:echo-dot-4-group" /></template>
