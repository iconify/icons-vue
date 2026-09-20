<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvq_dmzhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvq_dmzhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:fastly" /></template>
