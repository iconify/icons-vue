<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyz_wqbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="uyz_wqbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:align-right" /></template>
