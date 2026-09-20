<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obkojdbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obkojdbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:firstline-filled" /></template>
