<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3xs06bzl.css';
import '../../css/b/b1v-7vnuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3xs06bzl"/><path class="b1v-7vnuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-buildings" /></template>
