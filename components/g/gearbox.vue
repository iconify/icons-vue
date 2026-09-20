<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qad7z8bum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qad7z8bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:gearbox" /></template>
