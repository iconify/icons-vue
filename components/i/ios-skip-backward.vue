<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkzd7kuwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lkzd7kuwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-skip-backward" /></template>
