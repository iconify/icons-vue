<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wljf69bys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wljf69bys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heading-5-round" /></template>
