<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-1demrtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-1demrtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:hide-eye-crossbar" /></template>
