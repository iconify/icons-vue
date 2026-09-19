<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm4caib6z.css';
import '../../css/k/k7mhgvbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm4caib6z"/><path class="k7mhgvbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-webcam" /></template>
