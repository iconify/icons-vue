<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7op48boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7op48boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:artifact-hub" /></template>
