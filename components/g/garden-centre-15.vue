<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekslbabri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ekslbabri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:garden-centre-15" /></template>
