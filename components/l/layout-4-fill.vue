<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny_7ibb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ny_7ibb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-4-fill" /></template>
