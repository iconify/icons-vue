<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxzl7z52l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bxzl7z52l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:checkmark-circle" /></template>
