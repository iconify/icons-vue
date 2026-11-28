<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6zyok4pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6zyok4pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:desert" /></template>
