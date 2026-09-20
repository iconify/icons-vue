<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geqa0016h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geqa0016h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:critical" /></template>
