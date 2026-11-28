<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjr9atbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjr9atbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bowl-heart" /></template>
