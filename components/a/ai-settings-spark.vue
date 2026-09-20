<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzvzc6bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zzvzc6bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:ai-settings-spark" /></template>
