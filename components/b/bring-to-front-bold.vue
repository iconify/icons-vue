<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghv0-2b_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ghv0-2b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bring-to-front-bold" /></template>
