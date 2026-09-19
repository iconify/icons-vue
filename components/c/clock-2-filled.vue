<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtg72i0ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtg72i0ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clock-2-filled" /></template>
