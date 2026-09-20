<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyhu30znm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyhu30znm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:fmod" /></template>
