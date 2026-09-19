<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_2585bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="r_2585bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:barchartasc" /></template>
