<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldzssobld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ldzssobld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:flu-mask" /></template>
