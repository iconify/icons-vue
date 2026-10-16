<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9a328d8s.css';
import '../../css/t/thuizfb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p9a328d8s"/><path class="thuizfb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:junction-box-20" /></template>
