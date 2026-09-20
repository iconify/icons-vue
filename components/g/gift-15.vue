<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l12_aub-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l12_aub-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:gift-15" /></template>
