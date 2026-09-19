<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdej6-b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdej6-b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:file-plus-filled" /></template>
