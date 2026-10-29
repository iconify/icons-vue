<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ius514pkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ius514pkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:croissant-solid" /></template>
