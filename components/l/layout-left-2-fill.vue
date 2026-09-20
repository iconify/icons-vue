<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epg42eebu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epg42eebu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-left-2-fill" /></template>
