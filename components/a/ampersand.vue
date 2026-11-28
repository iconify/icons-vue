<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpmxipr_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpmxipr_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:ampersand" /></template>
