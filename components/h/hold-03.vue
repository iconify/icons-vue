<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzp351bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzp351bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hold-03" /></template>
