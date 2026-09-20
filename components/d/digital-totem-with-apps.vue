<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh76tebbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kh76tebbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:digital-totem-with-apps" /></template>
