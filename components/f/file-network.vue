<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlrbrtbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlrbrtbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-network" /></template>
