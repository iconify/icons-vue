<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2z0d68sn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x2z0d68sn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:align-horizontal-center" /></template>
