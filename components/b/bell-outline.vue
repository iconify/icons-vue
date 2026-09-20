<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n70mjmy2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="n70mjmy2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bell-outline" /></template>
