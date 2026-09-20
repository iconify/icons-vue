<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze611lb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ze611lb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:armchair2" /></template>
