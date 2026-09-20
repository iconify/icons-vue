<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp8p9sznl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dp8p9sznl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:drawing-pin" /></template>
