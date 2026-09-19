<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3-dh46ae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3-dh46ae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:calendar-alt-2-filled" /></template>
