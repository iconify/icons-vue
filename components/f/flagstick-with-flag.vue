<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igzplx7gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="igzplx7gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:flagstick-with-flag" /></template>
