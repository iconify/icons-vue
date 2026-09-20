<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pe_3scbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pe_3scbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:garage-line" /></template>
