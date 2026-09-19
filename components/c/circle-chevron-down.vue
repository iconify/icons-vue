<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccfvpkbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccfvpkbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:circle-chevron-down" /></template>
