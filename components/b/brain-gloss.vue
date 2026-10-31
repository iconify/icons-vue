<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw5-de5vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw5-de5vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:brain-gloss" /></template>
