<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt_9ord6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt_9ord6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-calendar-plus" /></template>
