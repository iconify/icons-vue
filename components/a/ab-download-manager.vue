<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o80r8jpae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o80r8jpae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ab-download-manager" /></template>
