<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahgmc5vep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahgmc5vep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heading-3-round" /></template>
