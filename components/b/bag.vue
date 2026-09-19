<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4f3d0b8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="j4f3d0b8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bag" /></template>
