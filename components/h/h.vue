<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-85kbc4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":466,"height":754};
const content = `<path class="t-85kbc4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:h" /></template>
