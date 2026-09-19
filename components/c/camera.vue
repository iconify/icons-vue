<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr3fmtb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fr3fmtb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:camera" /></template>
