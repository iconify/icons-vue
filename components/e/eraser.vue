<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmkih5h5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmkih5h5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:eraser" /></template>
