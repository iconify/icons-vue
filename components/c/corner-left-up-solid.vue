<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c725z4k7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c725z4k7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:corner-left-up-solid" /></template>
