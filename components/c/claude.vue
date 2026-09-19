<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxfrqbcqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nxfrqbcqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:claude" /></template>
