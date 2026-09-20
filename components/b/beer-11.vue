<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6wa-bbzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="h6wa-bbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:beer-11" /></template>
