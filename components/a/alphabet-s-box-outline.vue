<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwhz73bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwhz73bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alphabet-s-box-outline" /></template>
