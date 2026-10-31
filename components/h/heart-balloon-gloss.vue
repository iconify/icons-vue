<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpjo1kt9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpjo1kt9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-balloon-gloss" /></template>
