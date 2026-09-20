<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ap-28x_nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="ap-28x_nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:globeearth" /></template>
