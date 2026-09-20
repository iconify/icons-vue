<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p--21yv0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="p--21yv0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:banana-left" /></template>
