<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2q3-9bye.css';
import '../../css/s/s0b3vnblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2q3-9bye"/><path class="s0b3vnblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:export" /></template>
