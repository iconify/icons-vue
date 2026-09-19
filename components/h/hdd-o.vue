<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm2t39b3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1280};
const content = `<path class="cm2t39b3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hdd-o" /></template>
