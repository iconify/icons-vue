<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwnyw_b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nwnyw_b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:health-care-2-remix" /></template>
