<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quupx7b8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="quupx7b8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:city" /></template>
