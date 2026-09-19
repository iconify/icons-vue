<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ourt9_bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ourt9_bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:apple-airpods-max" /></template>
