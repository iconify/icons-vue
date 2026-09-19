<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8h9a8w2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8h9a8w2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:circle-half" /></template>
