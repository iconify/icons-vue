<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlr2llxyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="rlr2llxyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:infinite-2" /></template>
