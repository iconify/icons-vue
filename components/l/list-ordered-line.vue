<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdb262e9z.css';
import '../../css/s/svs9u_b2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdb262e9z"/><path class="svs9u_b2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-ordered-line" /></template>
