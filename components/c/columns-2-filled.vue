<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl1kiouvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl1kiouvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:columns-2-filled" /></template>
