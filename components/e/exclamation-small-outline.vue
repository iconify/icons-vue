<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uau_mgktq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uau_mgktq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:exclamation-small-outline" /></template>
