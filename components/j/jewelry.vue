<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpxjk91ta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="lpxjk91ta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:jewelry" /></template>
