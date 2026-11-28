<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r684nybuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r684nybuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bear-heart" /></template>
