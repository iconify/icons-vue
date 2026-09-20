<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxyt2_hbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hxyt2_hbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:half-star-1-remix" /></template>
