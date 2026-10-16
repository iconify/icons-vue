<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vayamib1a.css';
import '../../css/u/ut922vv1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vayamib1a"/><path class="ut922vv1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:junction-box-20-bold" /></template>
