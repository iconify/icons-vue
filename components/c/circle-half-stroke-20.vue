<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pepp-t52r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pepp-t52r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:circle-half-stroke-20" /></template>
