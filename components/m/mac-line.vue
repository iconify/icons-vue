<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-2gan1me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-2gan1me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mac-line" /></template>
