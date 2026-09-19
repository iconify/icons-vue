<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/porxiqwer.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="porxiqwer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:calendar-stroke-12" /></template>
