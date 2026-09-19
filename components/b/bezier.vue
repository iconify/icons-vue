<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we9h4vbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="we9h4vbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:bezier" /></template>
