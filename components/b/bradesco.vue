<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlvpmbbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":123,"height":23.1};
const content = `<path class="vlvpmbbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bradesco" /></template>
