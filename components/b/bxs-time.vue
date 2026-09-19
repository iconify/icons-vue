<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0_539bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0_539bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-time" /></template>
