<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qan7z0bas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qan7z0bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-square-fill" /></template>
