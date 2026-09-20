<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvji5lkkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvji5lkkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:check-rectangle-filled" /></template>
