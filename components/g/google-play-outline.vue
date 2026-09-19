<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iruq4jtgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iruq4jtgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:google-play-outline" /></template>
