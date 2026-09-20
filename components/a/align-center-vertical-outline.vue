<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8y38_bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m8y38_bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:align-center-vertical-outline" /></template>
