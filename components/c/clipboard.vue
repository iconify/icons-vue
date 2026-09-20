<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsebfebzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lsebfebzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:clipboard" /></template>
