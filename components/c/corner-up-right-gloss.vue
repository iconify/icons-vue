<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtdrmnbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtdrmnbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:corner-up-right-gloss" /></template>
