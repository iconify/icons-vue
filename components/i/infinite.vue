<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-90m7y5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="d-90m7y5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:infinite" /></template>
