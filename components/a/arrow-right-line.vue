<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzvw8wbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzvw8wbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-right-line" /></template>
