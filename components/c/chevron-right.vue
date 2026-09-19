<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omkiihvsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omkiihvsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:chevron-right" /></template>
