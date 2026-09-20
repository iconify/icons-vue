<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7228lb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u7228lb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anythingllm-light" /></template>
