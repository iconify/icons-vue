<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z64aqhpfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z64aqhpfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:frame" /></template>
