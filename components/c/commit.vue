<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_69oybqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l_69oybqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:commit" /></template>
