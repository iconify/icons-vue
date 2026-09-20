<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvdb1sbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvdb1sbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ice-cream-2-line" /></template>
