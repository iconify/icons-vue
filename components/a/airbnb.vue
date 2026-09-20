<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhahj9bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1991.3,"height":2143.2};
const content = `<path class="mhahj9bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:airbnb" /></template>
