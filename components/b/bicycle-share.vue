<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgr9lbbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sgr9lbbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bicycle-share" /></template>
