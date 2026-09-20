<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybkjwpbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybkjwpbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:copy-plus-filled" /></template>
