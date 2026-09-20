<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9_ix79gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t9_ix79gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:accusoft" /></template>
