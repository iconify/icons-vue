<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh8z6bbpj.css';
import '../../css/k/kpsumujvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mh8z6bbpj"/><path class="kpsumujvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clapperboard-20-bold" /></template>
