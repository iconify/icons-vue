<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0w_gdb6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0w_gdb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:code" /></template>
