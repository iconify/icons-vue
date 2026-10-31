<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-h14rbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-h14rbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:activity-gloss" /></template>
