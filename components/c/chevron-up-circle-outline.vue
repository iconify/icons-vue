<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_g_7jw1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_g_7jw1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-up-circle-outline" /></template>
