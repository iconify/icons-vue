<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab_k1v6wm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ab_k1v6wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hand-held-tablet-writing-solid" /></template>
