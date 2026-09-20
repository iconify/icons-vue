<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlsnkg_mt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlsnkg_mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:headphone" /></template>
