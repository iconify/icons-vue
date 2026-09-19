<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbjz_f1qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sbjz_f1qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:gitlab" /></template>
