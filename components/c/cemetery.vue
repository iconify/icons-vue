<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmti_bc9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wmti_bc9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:cemetery" /></template>
