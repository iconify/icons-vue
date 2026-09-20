<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkkij013w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="fkkij013w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:convenience-11" /></template>
