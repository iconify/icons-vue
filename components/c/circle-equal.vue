<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3j5vqbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3j5vqbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:circle-equal" /></template>
