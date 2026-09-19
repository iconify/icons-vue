<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7uoh_pkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="t7uoh_pkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:hammer" /></template>
