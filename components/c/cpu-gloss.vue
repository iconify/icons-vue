<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feavt8iof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="feavt8iof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cpu-gloss" /></template>
