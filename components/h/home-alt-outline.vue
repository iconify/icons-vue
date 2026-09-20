<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxx3bu1xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bxx3bu1xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:home-alt-outline" /></template>
