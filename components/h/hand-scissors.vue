<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r74fw468h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r74fw468h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:hand-scissors" /></template>
