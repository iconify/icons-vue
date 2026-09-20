<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et-0ovb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="et-0ovb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bbq" /></template>
