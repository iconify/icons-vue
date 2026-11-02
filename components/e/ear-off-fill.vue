<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arwizp_bx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arwizp_bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ear-off-fill" /></template>
