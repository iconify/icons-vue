<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9yfnao6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o9yfnao6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:band-aid-solid" /></template>
