<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6-vuobfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y6-vuobfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:facebook-outline" /></template>
