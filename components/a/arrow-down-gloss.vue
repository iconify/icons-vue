<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc2nu2bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc2nu2bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-down-gloss" /></template>
