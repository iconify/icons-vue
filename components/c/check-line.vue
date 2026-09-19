<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asf522r5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asf522r5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:check-line" /></template>
