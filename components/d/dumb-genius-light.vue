<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hej2h2wme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hej2h2wme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumb-genius-light" /></template>
