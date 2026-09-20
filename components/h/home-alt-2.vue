<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufv8hebkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ufv8hebkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:home-alt-2" /></template>
