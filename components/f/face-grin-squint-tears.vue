<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jravwy19z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jravwy19z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-grin-squint-tears" /></template>
