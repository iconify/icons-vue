<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf7twqfuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf7twqfuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:at-fill" /></template>
