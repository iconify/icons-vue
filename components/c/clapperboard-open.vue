<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxpt8w2zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mxpt8w2zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clapperboard-open" /></template>
