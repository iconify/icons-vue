<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ornma81re.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ornma81re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-note-1-line" /></template>
