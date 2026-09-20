<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq9sb-_fv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq9sb-_fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-arrow-left" /></template>
