<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox_5e8bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox_5e8bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calendar-plus-2" /></template>
