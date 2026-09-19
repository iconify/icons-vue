<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn2crwbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nn2crwbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:arrow-alt-circle-left" /></template>
