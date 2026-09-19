<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6-5tj1wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="i6-5tj1wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:hand-point-right" /></template>
