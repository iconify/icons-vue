<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybxol0kpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybxol0kpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:foursquare" /></template>
