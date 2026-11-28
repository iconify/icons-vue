<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox9k-ul3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox9k-ul3r primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:baseline-shift-duotone" /></template>
