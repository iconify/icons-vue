<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3joubhfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3joubhfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-paste" /></template>
