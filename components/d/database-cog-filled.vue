<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwreatbrt.css';
import '../../css/y/yg151vbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwreatbrt"/><path clip-rule="evenodd" class="yg151vbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:database-cog-filled" /></template>
