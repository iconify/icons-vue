<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_wig27sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_wig27sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bigcartel" /></template>
