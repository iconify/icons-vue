<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msklz-rvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msklz-rvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:display-filled" /></template>
