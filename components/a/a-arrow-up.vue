<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am_x09b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am_x09b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:a-arrow-up" /></template>
