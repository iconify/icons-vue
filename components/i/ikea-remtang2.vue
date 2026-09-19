<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ric394m0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ric394m0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-remtang2" /></template>
