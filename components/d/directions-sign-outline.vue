<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw2xqvbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vw2xqvbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:directions-sign-outline" /></template>
