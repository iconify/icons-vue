<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqhott-nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="kqhott-nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-down-left-box" /></template>
