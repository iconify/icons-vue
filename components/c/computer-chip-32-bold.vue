<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oahi-jwnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oahi-jwnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:computer-chip-32-bold" /></template>
