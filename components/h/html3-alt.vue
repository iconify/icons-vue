<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghs4zwbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghs4zwbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:html3-alt" /></template>
