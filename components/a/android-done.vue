<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku-6f_b2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ku-6f_b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-done" /></template>
