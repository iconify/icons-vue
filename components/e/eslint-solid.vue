<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4hduvb-v.css';
import '../../css/p/ppwhpebbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j4hduvb-v"/><path clip-rule="evenodd" class="ppwhpebbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:eslint-solid" /></template>
