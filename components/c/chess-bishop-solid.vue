<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s40586bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s40586bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:chess-bishop-solid" /></template>
