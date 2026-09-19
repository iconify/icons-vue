<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joh4lsb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="joh4lsb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:balloon-heart" /></template>
