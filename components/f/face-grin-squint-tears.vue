<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh-g3hbar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="yh-g3hbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:face-grin-squint-tears" /></template>
