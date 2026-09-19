<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8x7nbbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="u8x7nbbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:indent" /></template>
