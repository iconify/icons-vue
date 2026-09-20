<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-o21k_6n.css';
import '../../css/j/j3j2k6b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s-o21k_6n"/><path class="j3j2k6b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:cable" /></template>
