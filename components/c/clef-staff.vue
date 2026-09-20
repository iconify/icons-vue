<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imomcccqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imomcccqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clef-staff" /></template>
