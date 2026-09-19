<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyhvu77cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyhvu77cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dropdown-filled" /></template>
