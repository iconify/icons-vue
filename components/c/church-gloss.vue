<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd7wx3zmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd7wx3zmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:church-gloss" /></template>
