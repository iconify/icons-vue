<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waa-_0dyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waa-_0dyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:button-rounded-filled" /></template>
