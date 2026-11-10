<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1ra9z4op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1ra9z4op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:desklamp" /></template>
