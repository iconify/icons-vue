<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf2sa2bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jf2sa2bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:expand" /></template>
