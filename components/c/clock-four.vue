<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajs0hsgkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ajs0hsgkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:clock-four" /></template>
