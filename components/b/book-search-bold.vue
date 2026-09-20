<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av-303pwd.css';
import '../../css/g/giz0u4e7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="av-303pwd"/><path class="giz0u4e7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:book-search-bold" /></template>
