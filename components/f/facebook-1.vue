<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ona1muubo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ona1muubo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:facebook-1" /></template>
