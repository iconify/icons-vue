<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iier55b4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iier55b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:archive-restore-gloss" /></template>
