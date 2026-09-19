<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0_lmmbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":954};
const content = `<path class="p0_lmmbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:bar" /></template>
