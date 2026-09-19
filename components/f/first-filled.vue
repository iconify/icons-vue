<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdb3qisor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdb3qisor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:first-filled" /></template>
