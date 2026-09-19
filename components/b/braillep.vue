<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i86dc6bcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="i86dc6bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:braillep" /></template>
