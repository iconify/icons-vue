<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra9ry8b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra9ry8b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heading-1" /></template>
