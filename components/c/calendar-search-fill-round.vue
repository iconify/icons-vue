<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xit-_fb3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xit-_fb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-search-fill-round" /></template>
