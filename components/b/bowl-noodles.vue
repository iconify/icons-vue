<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af8zbz90e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af8zbz90e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bowl-noodles" /></template>
