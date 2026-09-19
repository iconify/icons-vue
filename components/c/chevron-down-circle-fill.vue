<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh4l6ogtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xh4l6ogtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-down-circle-fill" /></template>
