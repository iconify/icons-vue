<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqemarb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqemarb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:cake-line" /></template>
