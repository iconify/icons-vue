<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvwij9-lc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mvwij9-lc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:color-picker" /></template>
