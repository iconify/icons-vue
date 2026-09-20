<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl4gu9brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rl4gu9brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:desktop-alt-slash" /></template>
