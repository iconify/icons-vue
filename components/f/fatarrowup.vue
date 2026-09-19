<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-j074bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="e-j074bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:fatarrowup" /></template>
