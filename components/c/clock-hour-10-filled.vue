<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvxyzlvsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvxyzlvsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clock-hour-10-filled" /></template>
