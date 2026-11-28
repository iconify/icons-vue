<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikxmvscfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikxmvscfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:layers-check" /></template>
