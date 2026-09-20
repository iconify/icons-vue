<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fle9ceb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fle9ceb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kyocera" /></template>
