<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vobjp9-9u.css';
import '../../css/v/vgc92oekq.css';
import '../../css/f/fvq226bxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vobjp9-9u"/><path class="vgc92oekq"/><path class="fvq226bxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:cabridge-audio" /></template>
