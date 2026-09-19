<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6e2wm4vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="i6e2wm4vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-right-circle" /></template>
