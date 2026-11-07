<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpb5enzud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mpb5enzud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:hammer-20-solid" /></template>
