<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wco3rcpyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wco3rcpyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:list-bullet" /></template>
