<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4jjlrbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="b4jjlrbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:batteryempty" /></template>
