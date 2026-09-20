<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0sb-hbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="b0sb-hbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:heart-remix" /></template>
