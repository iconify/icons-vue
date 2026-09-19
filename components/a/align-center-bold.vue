<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_l676bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="v_l676bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:align-center-bold" /></template>
