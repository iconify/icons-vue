<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo1rnqugs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="yo1rnqugs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bee-fill" /></template>
