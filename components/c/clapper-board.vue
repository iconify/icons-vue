<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihhe6fw-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihhe6fw-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:clapper-board" /></template>
