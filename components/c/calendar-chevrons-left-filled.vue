<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6a5x9bff.css';
import '../../css/c/cwtdbgb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6a5x9bff"/><path class="cwtdbgb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-chevrons-left-filled" /></template>
