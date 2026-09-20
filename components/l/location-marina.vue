<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_ext6myn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b_ext6myn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:location-marina" /></template>
