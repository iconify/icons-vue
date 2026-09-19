<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiqbokbbo.css';
import '../../css/j/j0ryq4_tz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fiqbokbbo"/><path class="j0ryq4_tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:help-filled" /></template>
