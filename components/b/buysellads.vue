<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5kwqkbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="s5kwqkbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:buysellads" /></template>
