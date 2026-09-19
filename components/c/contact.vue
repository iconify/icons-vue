<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io23o0drw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io23o0drw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:contact" /></template>
