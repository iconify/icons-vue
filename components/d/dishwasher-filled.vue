<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjk_cab6w.css';
import '../../css/p/po-pxqb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjk_cab6w"/><path class="po-pxqb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dishwasher-filled" /></template>
