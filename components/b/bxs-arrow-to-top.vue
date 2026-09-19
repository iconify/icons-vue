<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo68l_7-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo68l_7-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-arrow-to-top" /></template>
