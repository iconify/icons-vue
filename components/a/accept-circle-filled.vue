<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-rn7nb-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="y-rn7nb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:accept-circle-filled" /></template>
