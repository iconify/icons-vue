<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd10hdc8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sd10hdc8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:diamonds-symbol-remix" /></template>
