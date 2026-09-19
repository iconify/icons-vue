<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x77m4fblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x77m4fblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:copyright" /></template>
