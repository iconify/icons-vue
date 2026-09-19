<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u33umgorm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="u33umgorm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lifesaver-fill-12" /></template>
