<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edr4xvbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edr4xvbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clockwise-alt-fill" /></template>
