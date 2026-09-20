<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fysu26aom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="fysu26aom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-down-circle-solid" /></template>
