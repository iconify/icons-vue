<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldh8llb9w.css';
import '../../css/o/o8vspab8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ldh8llb9w"/><path class="o8vspab8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-list-square-stroke-20" /></template>
