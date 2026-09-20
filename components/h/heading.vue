<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/synxj3bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="synxj3bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:heading" /></template>
