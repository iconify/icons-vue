<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnxm2eb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gnxm2eb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:arrow-bottom-right" /></template>
