<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gub9fbb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gub9fbb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:location" /></template>
