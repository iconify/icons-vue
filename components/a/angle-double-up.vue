<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq8ox75ei.css';
import '../../css/r/r3i--soji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path class="dq8ox75ei"/><path class="r3i--soji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:angle-double-up" /></template>
