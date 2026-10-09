<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewn1ke3br.css';
import '../../css/z/zgnbte-qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ewn1ke3br"/><path class="zgnbte-qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:columns-20" /></template>
