<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiwnycz9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiwnycz9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:calendar-remove-light" /></template>
