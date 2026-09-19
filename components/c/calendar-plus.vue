<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6lzsmb-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="z6lzsmb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:calendar-plus" /></template>
