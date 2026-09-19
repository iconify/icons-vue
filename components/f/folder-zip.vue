<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbdfjabgc.css';
import '../../css/j/jzq9heogi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbdfjabgc"/><path class="jzq9heogi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:folder-zip" /></template>
