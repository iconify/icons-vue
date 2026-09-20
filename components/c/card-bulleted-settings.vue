<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgpl1db7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgpl1db7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:card-bulleted-settings" /></template>
