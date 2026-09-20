<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tded57b5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tded57b5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:lightbulb-on" /></template>
