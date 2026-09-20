<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unfvigbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unfvigbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:eye-off-line" /></template>
