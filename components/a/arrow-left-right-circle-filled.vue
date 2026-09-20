<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgxy10d8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgxy10d8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-left-right-circle-filled" /></template>
