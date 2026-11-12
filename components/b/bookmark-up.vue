<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm2hk4b6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm2hk4b6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bookmark-up" /></template>
