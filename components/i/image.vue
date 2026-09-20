<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp8rpxbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xp8rpxbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:image" /></template>
