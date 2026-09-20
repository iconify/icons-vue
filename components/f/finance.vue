<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxk-ml5cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="gxk-ml5cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:finance" /></template>
