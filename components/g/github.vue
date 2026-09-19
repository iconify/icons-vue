<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olg2t05yp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":666};
const content = `<path class="olg2t05yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:github" /></template>
