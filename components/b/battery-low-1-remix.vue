<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2k90jzdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="u2k90jzdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:battery-low-1-remix" /></template>
