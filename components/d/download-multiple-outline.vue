<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_hb79b5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_hb79b5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:download-multiple-outline" /></template>
