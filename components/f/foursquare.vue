<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e079j9kul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1216,"height":1664};
const content = `<path class="e079j9kul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:foursquare" /></template>
