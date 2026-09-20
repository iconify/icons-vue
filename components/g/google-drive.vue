<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u653uebuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u653uebuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:google-drive" /></template>
