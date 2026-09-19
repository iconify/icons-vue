<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bin6v8b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bin6v8b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:battery-1-filled" /></template>
