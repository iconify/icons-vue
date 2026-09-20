<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm26zyb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm26zyb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:crayon" /></template>
