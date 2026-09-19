<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5mmr_g-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s5mmr_g-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:coffee" /></template>
