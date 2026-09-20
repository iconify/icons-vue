<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxot5i1qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxot5i1qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:foursquare" /></template>
