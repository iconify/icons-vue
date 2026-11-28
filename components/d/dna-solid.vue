<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiapstbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiapstbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:dna-solid" /></template>
