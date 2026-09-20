<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxlnqwbll.css';
import '../../css/o/ooafjrbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxlnqwbll"/><path class="ooafjrbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:creative-commons" /></template>
