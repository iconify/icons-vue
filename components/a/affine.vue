<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2o9v4b6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2o9v4b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:affine" /></template>
