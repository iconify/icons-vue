<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxeivydra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxeivydra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:liner" /></template>
