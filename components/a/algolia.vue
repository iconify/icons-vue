<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5c_go20t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="p5c_go20t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:algolia" /></template>
