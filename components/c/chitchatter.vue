<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzot9ebny.css';
import '../../css/e/eexszhbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jzot9ebny"/><path class="eexszhbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chitchatter" /></template>
