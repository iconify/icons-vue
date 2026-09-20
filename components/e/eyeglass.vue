<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awil3mfsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awil3mfsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:eyeglass" /></template>
