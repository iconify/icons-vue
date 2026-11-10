<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcdd04pos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcdd04pos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-x-mark" /></template>
