<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ouuz4eb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ouuz4eb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:anchor" /></template>
