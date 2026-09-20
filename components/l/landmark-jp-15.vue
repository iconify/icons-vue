<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj_h99bzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fj_h99bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:landmark-jp-15" /></template>
