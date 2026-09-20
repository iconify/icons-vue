<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9w-xz9jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r9w-xz9jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:magic-wand" /></template>
