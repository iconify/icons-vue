<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs4x2kvbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs4x2kvbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-u" /></template>
