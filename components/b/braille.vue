<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5-8qbbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2176,"height":1408};
const content = `<path class="q5-8qbbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:braille" /></template>
