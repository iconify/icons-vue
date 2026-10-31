<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_emwb22v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_emwb22v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-arrow-down-gloss" /></template>
