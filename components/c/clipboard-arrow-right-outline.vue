<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3x3cqb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3x3cqb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-arrow-right-outline" /></template>
