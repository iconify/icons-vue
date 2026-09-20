<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-dzn9u3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-dzn9u3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:google-marketing-platform" /></template>
