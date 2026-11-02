<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyt_8j3vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyt_8j3vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:delete-3-fill" /></template>
