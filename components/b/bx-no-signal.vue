<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvy83nzau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvy83nzau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-no-signal" /></template>
