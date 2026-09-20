<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk3x2jjys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk3x2jjys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:calendar-share" /></template>
