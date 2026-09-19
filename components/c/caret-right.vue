<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhwpcgbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yhwpcgbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:caret-right" /></template>
