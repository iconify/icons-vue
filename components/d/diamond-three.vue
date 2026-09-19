<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg1jh-27v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yg1jh-27v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:diamond-three" /></template>
