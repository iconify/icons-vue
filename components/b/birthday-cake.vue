<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyjf33b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="hyjf33b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:birthday-cake" /></template>
