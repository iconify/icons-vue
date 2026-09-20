<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjq_yy5-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjq_yy5-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:book-filled" /></template>
