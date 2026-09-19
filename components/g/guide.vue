<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjfhnp7yw.css';
import '../../css/c/cyhr1fblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mjfhnp7yw"/><path class="cyhr1fblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:guide" /></template>
