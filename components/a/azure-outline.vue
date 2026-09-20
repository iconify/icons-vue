<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djgtf2pqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="djgtf2pqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:azure-outline" /></template>
