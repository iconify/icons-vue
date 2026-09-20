<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia-bsglhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ia-bsglhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:anguished-face-with-spots-in-circle" /></template>
