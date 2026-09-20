<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woe5-fbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="woe5-fbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:heart-filled" /></template>
