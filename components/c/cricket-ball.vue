<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aud31ibrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aud31ibrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cricket-ball" /></template>
