<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-4w57b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-4w57b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-add-fill" /></template>
