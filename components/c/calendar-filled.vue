<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg0si9bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg0si9bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:calendar-filled" /></template>
