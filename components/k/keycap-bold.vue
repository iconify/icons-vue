<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3gx4zblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="p3gx4zblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:keycap-bold" /></template>
