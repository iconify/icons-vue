<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggi05pupf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":668};
const content = `<path class="ggi05pupf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:crown" /></template>
