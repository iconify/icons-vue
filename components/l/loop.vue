<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxkwrxb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cxkwrxb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:loop" /></template>
