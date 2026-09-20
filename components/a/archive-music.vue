<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhxs4nbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhxs4nbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:archive-music" /></template>
