<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc9m1-b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1664};
const content = `<path class="nc9m1-b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:facebook" /></template>
