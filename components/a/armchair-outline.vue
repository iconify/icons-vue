<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_qhlmp2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e_qhlmp2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:armchair-outline" /></template>
