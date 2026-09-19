<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqtjih4ab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqtjih4ab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:camera-plus-filled" /></template>
