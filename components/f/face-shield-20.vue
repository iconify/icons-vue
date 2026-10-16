<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax9d5gbpa.css';
import '../../css/w/w6rxgvl3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ax9d5gbpa"/><path class="w6rxgvl3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:face-shield-20" /></template>
