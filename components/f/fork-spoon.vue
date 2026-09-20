<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi4p9nbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="gi4p9nbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:fork-spoon" /></template>
