<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzc3xp45p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vzc3xp45p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lightbulb-on" /></template>
