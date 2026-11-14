<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spwdy4bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spwdy4bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:attachment-02" /></template>
