<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm7o4nb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pm7o4nb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:expand-horizontal-1-solid" /></template>
