<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz8-ezbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iz8-ezbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-big-up-20-bold" /></template>
