<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxfaztm6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="mxfaztm6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-left-solid" /></template>
