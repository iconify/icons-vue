<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foaefhbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="foaefhbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:hexagon-outline" /></template>
