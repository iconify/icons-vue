<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gugip7bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gugip7bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:dice-3" /></template>
