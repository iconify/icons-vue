<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p14jg4-rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p14jg4-rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:loan-filled" /></template>
