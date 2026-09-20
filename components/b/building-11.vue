<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hts6zhr3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="hts6zhr3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:building-11" /></template>
