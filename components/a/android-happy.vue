<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odb6au6vj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="odb6au6vj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-happy" /></template>
