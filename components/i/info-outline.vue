<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezy90kb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ezy90kb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:info-outline" /></template>
