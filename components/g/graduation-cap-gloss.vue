<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg1279bqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg1279bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:graduation-cap-gloss" /></template>
