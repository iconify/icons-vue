<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po1kqwbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po1kqwbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:diving-scuba" /></template>
