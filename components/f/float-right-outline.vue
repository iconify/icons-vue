<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6_haebsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x6_haebsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:float-right-outline" /></template>
