<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og9yjzwfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="og9yjzwfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:archive" /></template>
