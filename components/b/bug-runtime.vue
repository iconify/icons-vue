<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lximbrb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="lximbrb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:bug-runtime" /></template>
