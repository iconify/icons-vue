<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml-e1vb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ml-e1vb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-volume-up" /></template>
