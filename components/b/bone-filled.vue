<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdlu0zubj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdlu0zubj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bone-filled" /></template>
