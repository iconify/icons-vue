<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rse-n5zhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rse-n5zhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:high-voltage-sign" /></template>
