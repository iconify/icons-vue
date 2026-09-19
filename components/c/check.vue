<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-vvrxakq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p-vvrxakq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:check" /></template>
