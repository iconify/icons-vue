<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0h93f7on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l0h93f7on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:button" /></template>
