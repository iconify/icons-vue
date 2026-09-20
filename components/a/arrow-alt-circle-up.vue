<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtb87nb7y.css';
import '../../css/s/ssf66kbzi.css';
import '../../css/i/i7sr6ubzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtb87nb7y"/><path class="ssf66kbzi"/><path class="i7sr6ubzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-alt-circle-up" /></template>
