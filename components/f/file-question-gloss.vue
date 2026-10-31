<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxex_nckp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxex_nckp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-question-gloss" /></template>
