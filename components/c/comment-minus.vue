<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os_7itbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="os_7itbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:comment-minus" /></template>
