<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq812ab-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq812ab-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gogdotcom" /></template>
