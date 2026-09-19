<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trlqebcfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="trlqebcfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:face-split" /></template>
