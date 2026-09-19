<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3wpudb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":737};
const content = `<path class="y3wpudb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:glasses" /></template>
