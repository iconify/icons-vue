<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf2qmgbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xf2qmgbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:dollar-solid" /></template>
