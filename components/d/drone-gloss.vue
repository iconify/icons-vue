<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc27ceb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc27ceb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:drone-gloss" /></template>
