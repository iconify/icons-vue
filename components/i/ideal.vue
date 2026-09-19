<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqbp4m68q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="kqbp4m68q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:ideal" /></template>
