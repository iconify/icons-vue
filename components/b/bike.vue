<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk3pjmb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qk3pjmb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:bike" /></template>
