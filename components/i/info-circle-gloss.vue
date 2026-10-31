<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9mbz718s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9mbz718s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:info-circle-gloss" /></template>
