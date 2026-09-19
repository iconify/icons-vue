<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3xs06bzl.css';
import '../../css/i/i19gygbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3xs06bzl"/><path class="i19gygbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:buildings" /></template>
