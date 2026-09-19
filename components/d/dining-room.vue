<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clchc7ilh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="clchc7ilh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:dining-room" /></template>
