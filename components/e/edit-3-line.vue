<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-pk5x7ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-pk5x7ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:edit-3-line" /></template>
