<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7gie67ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":52,"height":28};
const content = `<path clip-rule="evenodd" class="s7gie67ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cisco-light" /></template>
