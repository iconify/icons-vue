<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0gc6gddm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="o0gc6gddm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:align-text-center-solid" /></template>
