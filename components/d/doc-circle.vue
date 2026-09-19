<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/druxve_op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="druxve_op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:doc-circle" /></template>
