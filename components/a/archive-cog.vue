<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffok7h96d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffok7h96d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:archive-cog" /></template>
