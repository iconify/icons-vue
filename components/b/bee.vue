<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_uinibpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_uinibpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bee" /></template>
