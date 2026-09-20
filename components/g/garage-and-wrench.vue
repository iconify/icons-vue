<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um98v6b5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="um98v6b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:garage-and-wrench" /></template>
