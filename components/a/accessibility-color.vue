<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-u4xnbot.css';
import '../../css/b/b1gskgvdy.css';
import '../../css/s/svdy80z7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m-u4xnbot"/><path class="b1gskgvdy"/><path class="svdy80z7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:accessibility-color" /></template>
