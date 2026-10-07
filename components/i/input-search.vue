<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmbd2pb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmbd2pb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:input-search" /></template>
