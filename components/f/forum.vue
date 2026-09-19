<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw63rpeky.css';
import '../../css/m/mfbf4utcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lw63rpeky"/><path class="mfbf4utcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:forum" /></template>
