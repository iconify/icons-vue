<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlmu-owkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="jlmu-owkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:filter-alt-4" /></template>
