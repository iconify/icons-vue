<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz5k5b0_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lz5k5b0_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cat-sitting-and-whistle" /></template>
