<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sim1-4btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sim1-4btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:battery-2-line" /></template>
