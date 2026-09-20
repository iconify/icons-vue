<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc20habja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc20habja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrowhead-down" /></template>
