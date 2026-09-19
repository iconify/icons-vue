<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2bivto0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":512};
const content = `<path class="k2bivto0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:golf-ball" /></template>
