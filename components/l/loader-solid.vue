<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n54nlf2gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="n54nlf2gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:loader-solid" /></template>
