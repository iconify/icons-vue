<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq-vnvxgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq-vnvxgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cocktail" /></template>
