<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-bsaz-tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="m-bsaz-tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:castle-jp-11" /></template>
