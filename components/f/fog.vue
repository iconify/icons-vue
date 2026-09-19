<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdd35gb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pdd35gb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:fog" /></template>
