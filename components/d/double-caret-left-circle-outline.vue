<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubb0mibui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ubb0mibui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-left-circle-outline" /></template>
