<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7v4qmbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7v4qmbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-tag-alt" /></template>
