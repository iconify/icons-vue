<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7e500buh.css';
import '../../css/g/gk7nwhbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o7e500buh"/><path class="gk7nwhbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:frying-pan-20" /></template>
