<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4fu23kqa.css';
import '../../css/p/p--gbnsrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v4fu23kqa"/><path class="p--gbnsrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:beauty-mirror-2" /></template>
