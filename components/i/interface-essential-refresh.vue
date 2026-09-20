<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxxzk5b7h.css';
import '../../css/c/c06gyab9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yxxzk5b7h"/><path class="c06gyab9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-refresh" /></template>
