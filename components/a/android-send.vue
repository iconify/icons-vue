<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm3sd0tjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lm3sd0tjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-send" /></template>
