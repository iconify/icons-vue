<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktesybb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktesybb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-left-thick" /></template>
