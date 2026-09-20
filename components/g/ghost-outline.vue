<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drzuurbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="drzuurbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:ghost-outline" /></template>
