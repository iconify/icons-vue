<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arccr3b_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="arccr3b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:layout-window-2-remix" /></template>
