<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk3e8abzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk3e8abzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:house-line" /></template>
