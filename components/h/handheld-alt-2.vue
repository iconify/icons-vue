<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rayco9bbe.css';
import '../../css/p/p1v9mob6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rayco9bbe"/><path class="p1v9mob6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:handheld-alt-2" /></template>
