<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m26zf4yei.css';
import '../../css/o/odibfhbmi.css';
import '../../css/c/czl7urd3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m26zf4yei"/><path class="odibfhbmi"/><path class="czl7urd3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:hand-little-finger" /></template>
