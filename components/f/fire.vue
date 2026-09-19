<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp-nd7g4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":424,"height":496};
const content = `<path class="xp-nd7g4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:fire" /></template>
