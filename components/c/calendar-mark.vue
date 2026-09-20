<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if30i5bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="if30i5bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:calendar-mark" /></template>
