<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p03e-lbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p03e-lbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-up-small-outline" /></template>
