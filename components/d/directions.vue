<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v24apqbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v24apqbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:directions" /></template>
