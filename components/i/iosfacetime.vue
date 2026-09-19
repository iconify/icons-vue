<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j60i7hb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j60i7hb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:iosfacetime" /></template>
