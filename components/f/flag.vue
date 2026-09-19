<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql38_tbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":850};
const content = `<path class="ql38_tbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:flag" /></template>
