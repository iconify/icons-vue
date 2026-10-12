<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teke80b1t.css';
import '../../css/s/srka-7bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teke80b1t"/><path class="srka-7bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-heart-filled" /></template>
