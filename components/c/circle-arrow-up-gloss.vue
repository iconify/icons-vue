<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb5lmg94y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb5lmg94y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-arrow-up-gloss" /></template>
