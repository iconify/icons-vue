<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzfogzbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":59,"height":59,"left":582,"top":232.67};
const content = `<path class="gzfogzbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lumin-light" /></template>
