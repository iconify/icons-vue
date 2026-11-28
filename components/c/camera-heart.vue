<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/agw2k9bgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agw2k9bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:camera-heart" /></template>
