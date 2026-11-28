<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-kyxtbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-kyxtbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:dice-3" /></template>
