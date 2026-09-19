<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdfm1we6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdfm1we6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:border-top" /></template>
