<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6dfqptcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6dfqptcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevrons-up-down-solid" /></template>
