<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j00phfbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j00phfbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:activity" /></template>
