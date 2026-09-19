<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi870p-xs.css';
import '../../css/f/fcxs7zbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vi870p-xs"/><path class="fcxs7zbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:hand" /></template>
