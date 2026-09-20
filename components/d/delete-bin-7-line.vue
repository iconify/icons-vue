<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb_-dwb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb_-dwb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:delete-bin-7-line" /></template>
