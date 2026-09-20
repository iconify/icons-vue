<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq7toobzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq7toobzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ankh" /></template>
