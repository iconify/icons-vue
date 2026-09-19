<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnu1m9b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnu1m9b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:compare-states-outlined" /></template>
