<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0g7uzbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0g7uzbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-pen-sharp" /></template>
