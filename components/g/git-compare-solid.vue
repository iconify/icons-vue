<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip6956biy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ip6956biy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:git-compare-solid" /></template>
