<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbjlf-v6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbjlf-v6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:apps-2-add-line" /></template>
