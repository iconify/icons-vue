<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chluebbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chluebbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bee-gloss" /></template>
