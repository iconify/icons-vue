<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k61q2-brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k61q2-brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:logs-gloss" /></template>
