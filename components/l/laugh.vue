<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aziub6dhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aziub6dhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:laugh" /></template>
