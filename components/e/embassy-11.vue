<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwnm_cc8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="uwnm_cc8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:embassy-11" /></template>
