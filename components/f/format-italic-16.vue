<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx-eyubof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jx-eyubof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:format-italic-16" /></template>
