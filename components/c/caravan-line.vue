<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk5libcxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk5libcxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:caravan-line" /></template>
