<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bchgvkbbo.css';
import '../../css/c/cy37qpj-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bchgvkbbo"/><path class="cy37qpj-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:hand-fight-2-finger" /></template>
