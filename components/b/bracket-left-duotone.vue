<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8t1iqbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8t1iqbse primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bracket-left-duotone" /></template>
