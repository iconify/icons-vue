<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxff6ebhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hxff6ebhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:battery-full-1-remix" /></template>
