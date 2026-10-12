<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g11id0skg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g11id0skg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-filled" /></template>
