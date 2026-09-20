<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqjlhxegv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tqjlhxegv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:align-bottom-solid" /></template>
