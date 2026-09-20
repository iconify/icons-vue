<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugtm5y13q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugtm5y13q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bentoml" /></template>
