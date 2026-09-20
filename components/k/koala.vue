<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-jsh9bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-jsh9bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:koala" /></template>
