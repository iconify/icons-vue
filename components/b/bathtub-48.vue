<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvkgehx6a.css';
import '../../css/f/fo-j22b0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jvkgehx6a"/><path class="fo-j22b0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bathtub-48" /></template>
