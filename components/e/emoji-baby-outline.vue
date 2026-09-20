<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgjys7brw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgjys7brw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoji-baby-outline" /></template>
