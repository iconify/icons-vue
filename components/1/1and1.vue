<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsq6jsz0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsq6jsz0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:1and1" /></template>
