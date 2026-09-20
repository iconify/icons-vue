<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btz72t84e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btz72t84e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fur-affinity" /></template>
