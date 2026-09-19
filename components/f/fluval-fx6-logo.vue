<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5e2rrbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5e2rrbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:fluval-fx6-logo" /></template>
