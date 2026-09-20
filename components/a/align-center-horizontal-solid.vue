<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmkk7pd3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gmkk7pd3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:align-center-horizontal-solid" /></template>
