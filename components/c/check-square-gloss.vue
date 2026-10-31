<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5iajr7ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5iajr7ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:check-square-gloss" /></template>
