<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv07jkb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv07jkb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrows-resize" /></template>
