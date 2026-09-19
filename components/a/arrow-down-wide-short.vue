<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypl7m5fud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ypl7m5fud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-down-wide-short" /></template>
