<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2o5l269j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2o5l269j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:laptop" /></template>
